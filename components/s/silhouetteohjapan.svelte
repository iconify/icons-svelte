<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qetnckbkp.css';
import '../../css/y/ya1w5kb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qetnckbkp"/><path class="ya1w5kb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:silhouetteohjapan" {...props}></Icon>
