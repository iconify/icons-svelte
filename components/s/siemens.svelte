<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c64i70y5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c64i70y5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:siemens" {...props}></Icon>
