<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndoo8eizj.css';
import '../../css/n/npq26_zsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ndoo8eizj"/><path class="npq26_zsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:voltmeter-48" {...props}></Icon>
