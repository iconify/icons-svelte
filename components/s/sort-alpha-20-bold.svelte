<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0heepbom.css';
import '../../css/f/fusgjgx2r.css';
import '../../css/e/egctjry8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d0heepbom"/><path class="fusgjgx2r"/><path class="egctjry8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-alpha-20-bold" {...props}></Icon>
