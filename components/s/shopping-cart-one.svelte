<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p2axamk9n.css';
import '../../css/k/k9eyo1h_u.css';
import '../../css/a/amfdxgb4w.css';
import '../../css/q/q79nj4brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><circle class="p2axamk9n"/><circle class="k9eyo1h_u"/><path class="amfdxgb4w"/><path class="q79nj4brv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shopping-cart-one" {...props}></Icon>
