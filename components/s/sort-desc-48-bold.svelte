<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgv9v9bka.css';
import '../../css/t/t1k7qpc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kgv9v9bka"/><path class="t1k7qpc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-desc-48-bold" {...props}></Icon>
