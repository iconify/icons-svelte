<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7rg3yq0g.css';
import '../../css/w/wzoutn_0j.css';
import '../../css/y/y9mg2tbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7rg3yq0g"/><path class="wzoutn_0j"/><path class="y9mg2tbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-check-48-bold" {...props}></Icon>
