<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9y477w0i.css';
import '../../css/w/wwbiboy9e.css';
import '../../css/l/l1vwvkb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="n9y477w0i"/><path class="wwbiboy9e"/><path clip-rule="evenodd" class="l1vwvkb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifier-bug-bold-duotone" {...props}></Icon>
