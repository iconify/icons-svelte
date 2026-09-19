<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu8bbgk9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pu8bbgk9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:v-outline" {...props}></Icon>
