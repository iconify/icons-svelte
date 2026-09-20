<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmsc_gbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmsc_gbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vidu" {...props}></Icon>
