<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjzw4bccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjzw4bccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:subtitle-edit" {...props}></Icon>
