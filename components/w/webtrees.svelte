<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al0ngib-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al0ngib-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webtrees" {...props}></Icon>
