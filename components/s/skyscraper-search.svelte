<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwuacpr-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwuacpr-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:skyscraper-search" {...props}></Icon>
