<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojldz2bdb.css';
import '../../css/v/v4b9abtis.css';
import '../../css/o/os-6ceb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojldz2bdb"/><path class="v4b9abtis"/><path class="os-6ceb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stirling-pdf-dark" {...props}></Icon>
