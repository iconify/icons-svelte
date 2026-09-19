<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucgba-79t.css';
import '../../css/y/yeeel25yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucgba-79t"/><path class="yeeel25yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:speaker-outline" {...props}></Icon>
