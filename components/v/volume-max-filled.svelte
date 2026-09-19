<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6chq9yvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l6chq9yvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:volume-max-filled" {...props}></Icon>
