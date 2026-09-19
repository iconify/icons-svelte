<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j86zfcbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j86zfcbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:shower" {...props}></Icon>
