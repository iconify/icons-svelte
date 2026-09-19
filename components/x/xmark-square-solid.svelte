<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgy6kkdjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgy6kkdjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:xmark-square-solid" {...props}></Icon>
