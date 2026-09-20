<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isgee_aqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isgee_aqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-models-resource" {...props}></Icon>
