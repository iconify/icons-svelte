<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/acmhcgbix.css';
import '../../css/z/z8j9m1bjy.css';
import '../../css/g/gdtht-o7n.css';
import '../../css/g/gzu3vyboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="acmhcgbix"/><path class="z8j9m1bjy"/><path class="gdtht-o7n"/><path class="gzu3vyboy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wallet-line-duotone" {...props}></Icon>
