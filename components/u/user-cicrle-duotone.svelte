<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adezxkbcn.css';
import '../../css/h/hana-fm8g.css';
import '../../css/w/wusbso8md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adezxkbcn"/><circle class="hana-fm8g"/><path clip-rule="evenodd" class="wusbso8md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-cicrle-duotone" {...props}></Icon>
