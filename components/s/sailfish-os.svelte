<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fos-ok0ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fos-ok0ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sailfish-os" {...props}></Icon>
