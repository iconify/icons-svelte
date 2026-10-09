<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpgzfijku.css';
import '../../css/h/hvaaohf8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jpgzfijku"/><path class="hvaaohf8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-blade-20" {...props}></Icon>
