<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx7mb-bib.css';
import '../../css/z/zapq_sb9r.css';
import '../../css/y/y_knajrym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx7mb-bib"/><path class="zapq_sb9r"/><path class="y_knajrym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wifi" {...props}></Icon>
