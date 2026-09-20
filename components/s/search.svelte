<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/u/udwt2i.css';
import '../../css/z/zwfx-h.css';
import '../../css/s/so-from-40.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c udwt2i"/><path class="a0m25c zwfx-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:search" {...props}></Icon>
