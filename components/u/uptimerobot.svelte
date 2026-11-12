<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9vcwpudw.css';
import '../../css/b/b5b9_cc2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="v9vcwpudw"/><circle class="b5b9_cc2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uptimerobot" {...props}></Icon>
