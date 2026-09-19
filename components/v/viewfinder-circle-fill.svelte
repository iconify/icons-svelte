<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-u3txb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="w-u3txb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:viewfinder-circle-fill" {...props}></Icon>
