<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5b5kzb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o5b5kzb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:table-cells-16-solid" {...props}></Icon>
