<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9czz4bal.css';
import '../../css/k/kpj7x2bvw.css';
import '../../css/g/gy9jckxha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d9czz4bal"/><path class="kpj7x2bvw"/><path class="gy9jckxha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-home-48" {...props}></Icon>
