<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-wsdua2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-wsdua2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:thewashingtonpost" {...props}></Icon>
