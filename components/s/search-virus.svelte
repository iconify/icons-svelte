<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp-6atb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gp-6atb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:search-virus" {...props}></Icon>
