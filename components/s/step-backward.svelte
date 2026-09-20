<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csz_dqbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="csz_dqbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:step-backward" {...props}></Icon>
