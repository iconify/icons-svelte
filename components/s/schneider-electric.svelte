<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9f89qgib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9f89qgib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:schneider-electric" {...props}></Icon>
