<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwingb7ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kwingb7ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:tb" {...props}></Icon>
