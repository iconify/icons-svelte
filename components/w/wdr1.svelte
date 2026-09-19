<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgh33qb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgh33qb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:wdr1" {...props}></Icon>
