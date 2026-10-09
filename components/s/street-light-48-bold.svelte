<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be-3goh7n.css';
import '../../css/d/do-2pcc7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="be-3goh7n"/><path class="do-2pcc7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:street-light-48-bold" {...props}></Icon>
