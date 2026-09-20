<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qria0dbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qria0dbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:spine" {...props}></Icon>
