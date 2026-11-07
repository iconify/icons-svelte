<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4w_uybke.css';
import '../../css/d/dohz_0b7q.css';
import '../../css/x/x1lme2b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4w_uybke"/><path class="dohz_0b7q"/><path class="x1lme2b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scale-bold-duotone" {...props}></Icon>
