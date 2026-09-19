<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njo7p1bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="njo7p1bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:table-tennis-paddle-and-ball" {...props}></Icon>
