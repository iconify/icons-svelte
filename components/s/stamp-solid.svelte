<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8-2egbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m8-2egbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:stamp-solid" {...props}></Icon>
