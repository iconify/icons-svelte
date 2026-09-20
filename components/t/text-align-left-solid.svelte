<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndmtz2bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndmtz2bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:text-align-left-solid" {...props}></Icon>
