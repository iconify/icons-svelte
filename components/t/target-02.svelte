<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h4pc6jngq.css';
import '../../css/w/wkm6c6j9i.css';
import '../../css/a/a5k_nab9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h4pc6jngq"/><path class="wkm6c6j9i"/><path class="a5k_nab9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:target-02" {...props}></Icon>
