<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdlmnabbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="mdlmnabbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:search-1" {...props}></Icon>
