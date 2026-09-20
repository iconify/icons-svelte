<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2o_znbdb.css';
import '../../css/v/vh7rfhbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2o_znbdb"/><path clip-rule="evenodd" class="vh7rfhbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:trash-full-16" {...props}></Icon>
