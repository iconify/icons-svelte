<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/s/sihh1k.css';
import '../../css/z/ztfx7w.css';
import '../../css/s/so-from-24.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c sihh1k"/><path class="a0m25c ztfx7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:turn-left" {...props}></Icon>
