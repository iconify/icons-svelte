<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xamtaihib.css';
import '../../css/b/bc70y0nuy.css';
import '../../css/o/oqexibvmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xamtaihib"/><circle class="bc70y0nuy"/><path class="oqexibvmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:warning" {...props}></Icon>
