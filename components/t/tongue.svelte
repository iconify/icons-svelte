<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr_jmhjqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fr_jmhjqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:tongue" {...props}></Icon>
