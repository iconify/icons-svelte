<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-qy24b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-qy24b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:watch" {...props}></Icon>
