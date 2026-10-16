<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar2h8rs6u.css';
import '../../css/f/fd1yhqbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ar2h8rs6u"/><path class="fd1yhqbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tabs-48" {...props}></Icon>
