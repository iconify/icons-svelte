<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmvgk8zqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmvgk8zqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:webtrees" {...props}></Icon>
