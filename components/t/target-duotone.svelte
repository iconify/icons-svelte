<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4i2ew1ke.css';
import '../../css/z/znvy83hys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path clip-rule="evenodd" class="znvy83hys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:target-duotone" {...props}></Icon>
