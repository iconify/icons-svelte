<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e37f7lbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e37f7lbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:under-armour" {...props}></Icon>
