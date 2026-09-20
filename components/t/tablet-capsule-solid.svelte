<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz5y_9bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zz5y_9bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tablet-capsule-solid" {...props}></Icon>
