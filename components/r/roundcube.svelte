<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbqtq-4ae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbqtq-4ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:roundcube" {...props}></Icon>
