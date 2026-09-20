<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/libkqqbsb.css';
import '../../css/u/u44crn52a.css';
import '../../css/a/af5m2ccgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="libkqqbsb"/><path clip-rule="evenodd" class="u44crn52a"/><path class="af5m2ccgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rss-solid" {...props}></Icon>
