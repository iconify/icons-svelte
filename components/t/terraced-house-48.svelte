<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc7h1ybso.css';
import '../../css/s/saf2gf3kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bc7h1ybso"/><path class="saf2gf3kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terraced-house-48" {...props}></Icon>
