<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uayr9jbjw.css';
import '../../css/e/ebana2mce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uayr9jbjw"/><path class="ebana2mce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sea-level-rise-48-bold" {...props}></Icon>
