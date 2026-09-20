<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlhue_74y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlhue_74y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sao-paulo-metro" {...props}></Icon>
