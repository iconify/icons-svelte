<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga_p24znu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ga_p24znu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sesame" {...props}></Icon>
