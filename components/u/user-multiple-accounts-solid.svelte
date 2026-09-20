<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-c4_905v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r-c4_905v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:user-multiple-accounts-solid" {...props}></Icon>
