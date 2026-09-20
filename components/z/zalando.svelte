<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqrrfm5ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqrrfm5ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zalando" {...props}></Icon>
