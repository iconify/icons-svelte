<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlttyjbjw.css';
import '../../css/y/ymagrdb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlttyjbjw"/><path class="ymagrdb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-share-ios" {...props}></Icon>
