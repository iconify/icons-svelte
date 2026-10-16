<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdb19jl6q.css';
import '../../css/q/q037hgbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pdb19jl6q"/><path class="q037hgbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:used-cooking-oil-20" {...props}></Icon>
