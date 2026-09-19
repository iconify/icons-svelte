<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi5iwqbby.css';
import '../../css/q/qqdx66bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wi5iwqbby"/><path class="qqdx66bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vagrant-wordmark" {...props}></Icon>
