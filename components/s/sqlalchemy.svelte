<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov5v3-62v.css';
import '../../css/h/h-s431bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ov5v3-62v"/><path class="h-s431bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sqlalchemy" {...props}></Icon>
