<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heh8_qbzw.css';
import '../../css/j/jqemctbeh.css';
import '../../css/l/l7fkvo-fr.css';
import '../../css/m/moj4tsily.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="heh8_qbzw"/><path class="jqemctbeh"/><path class="l7fkvo-fr"/><path class="moj4tsily"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-array-sun-20-bold" {...props}></Icon>
