<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx0pw3fls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gx0pw3fls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:table-cells-merge-solid" {...props}></Icon>
