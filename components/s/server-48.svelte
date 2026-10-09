<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mniqmdgfa.css';
import '../../css/o/onpzv9a2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mniqmdgfa"/><path class="onpzv9a2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:server-48" {...props}></Icon>
