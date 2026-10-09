<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gffnzrbyj.css';
import '../../css/d/d3xlh_egt.css';
import '../../css/b/bhb3myb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gffnzrbyj"/><path class="d3xlh_egt"/><path class="bhb3myb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transformer-20-bold" {...props}></Icon>
