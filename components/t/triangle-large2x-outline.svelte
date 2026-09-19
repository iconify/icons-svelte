<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an9bkgbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="an9bkgbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-large2x-outline" {...props}></Icon>
