<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht_mu-b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ht_mu-b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:umbrella-outline" {...props}></Icon>
