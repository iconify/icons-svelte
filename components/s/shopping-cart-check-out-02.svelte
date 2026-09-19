<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t70z745yv.css';
import '../../css/t/tid15ec6o.css';
import '../../css/o/o50ddxiay.css';
import '../../css/b/b-v3dtbhs.css';
import '../../css/f/fe1mv7ygx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t70z745yv"/><path class="tid15ec6o"/><circle class="o50ddxiay"/><circle class="b-v3dtbhs"/><path class="fe1mv7ygx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shopping-cart-check-out-02" {...props}></Icon>
