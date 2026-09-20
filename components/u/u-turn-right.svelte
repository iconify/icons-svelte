<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/i/i15xoo.css';
import '../../css/t/th6o3g.css';
import '../../css/s/so-from-36.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c i15xoo"/><path class="a0m25c th6o3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:u-turn-right" {...props}></Icon>
