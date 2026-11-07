<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti_9tgx1a.css';
import '../../css/q/qpq6tjknf.css';
import '../../css/s/su7532b5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti_9tgx1a"/><path class="qpq6tjknf"/><path clip-rule="evenodd" class="su7532b5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-2-outline" {...props}></Icon>
