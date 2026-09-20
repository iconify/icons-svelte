<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3nu8lbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3nu8lbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:times-square-solid" {...props}></Icon>
