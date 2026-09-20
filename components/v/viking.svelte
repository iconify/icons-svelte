<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_cbxqb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k_cbxqb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:viking" {...props}></Icon>
