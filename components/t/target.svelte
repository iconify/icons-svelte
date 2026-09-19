<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbp2n_b0d.css';
import '../../css/w/wyddhdbvg.css';
import '../../css/w/weozcygjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="gbp2n_b0d"/><path class="wyddhdbvg"/><circle class="weozcygjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:target" {...props}></Icon>
