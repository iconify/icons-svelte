<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftg0kf3yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ftg0kf3yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:volume-max" {...props}></Icon>
