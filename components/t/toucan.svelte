<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe48pf9zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xe48pf9zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:toucan" {...props}></Icon>
