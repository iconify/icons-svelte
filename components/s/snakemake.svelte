<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai6onkxos.css';
import '../../css/p/puojo9i0c.css';
import '../../css/w/wd2296cyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ai6onkxos"/><path class="puojo9i0c"/><path class="wd2296cyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:snakemake" {...props}></Icon>
