<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa0z9ccux.css';
import '../../css/c/cdardccke.css';
import '../../css/t/tkbzu4bpe.css';
import '../../css/w/wujjhtesw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xa0z9ccux"/><path class="cdardccke"/><path class="tkbzu4bpe"/><path class="wujjhtesw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sim-card-20" {...props}></Icon>
