<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7lq-ab2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7lq-ab2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:shiny-iris" {...props}></Icon>
