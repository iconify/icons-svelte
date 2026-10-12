<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r86lgubxd.css';
import '../../css/f/foj_0087j.css';
import '../../css/c/cch-u1bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r86lgubxd"/><path class="foj_0087j"/><path class="cch-u1bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stethoscope-20" {...props}></Icon>
