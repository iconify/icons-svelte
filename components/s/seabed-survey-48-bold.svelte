<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b611vubcy.css';
import '../../css/f/fg-wh3qoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b611vubcy"/><path class="fg-wh3qoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seabed-survey-48-bold" {...props}></Icon>
