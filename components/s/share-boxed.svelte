<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn6csrh5o.css';
import '../../css/c/cpg14cc3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sn6csrh5o"/><path class="cpg14cc3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:share-boxed" {...props}></Icon>
