<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d90r3_bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d90r3_bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:sqlalchemy" {...props}></Icon>
