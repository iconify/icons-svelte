<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aedcft.css';
import '../../css/a/a0m25c.css';
import '../../css/b/bsgi6p.css';
import '../../css/v/vwcgvo.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-34.css';
import '../../css/s/so-from-16.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aedcft"/><path class="a0m25c bsgi6p"/><path class="a0m25c vwcgvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-half-alt-twotone" {...props}></Icon>
