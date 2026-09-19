<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6qt5nqnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6qt5nqnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:wordpress-alt" {...props}></Icon>
