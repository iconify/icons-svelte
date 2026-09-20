<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oii--ihhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oii--ihhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:webmin" {...props}></Icon>
