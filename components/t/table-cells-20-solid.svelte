<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_6z5b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nz_6z5b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:table-cells-20-solid" {...props}></Icon>
