<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/a1149j1wh.css';
import '../../css/g/gx4ah_6qi.css';
import '../../css/n/nc5jv0bhh.css';
import '../../css/a/a9vsgkbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a1149j1wh"/><circle class="gx4ah_6qi"/><circle class="nc5jv0bhh"/><circle class="a9vsgkbga"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:sliders" {...props}></Icon>
