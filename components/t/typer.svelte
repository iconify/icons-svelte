<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni_8jsb-d.css';
import '../../css/t/tblwxac3r.css';
import '../../css/b/bkf_frbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<rect class="ni_8jsb-d"/><rect class="tblwxac3r"/><path class="bkf_frbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:typer" {...props}></Icon>
