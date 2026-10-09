<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghq0elqau.css';
import '../../css/f/fzoldhk-f.css';
import '../../css/f/fz14dobdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ghq0elqau"/><path class="fzoldhk-f"/><path class="fz14dobdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:time-of-use-48-bold" {...props}></Icon>
