<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kftv5qb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kftv5qb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-individual-suite" {...props}></Icon>
