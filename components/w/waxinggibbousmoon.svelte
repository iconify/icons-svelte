<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb2gfqb4x.css';
import '../../css/h/hmk4n3ura.css';
import '../../css/u/uqb8_ebby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rb2gfqb4x"/><path class="hmk4n3ura"/><path class="uqb8_ebby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:waxinggibbousmoon" {...props}></Icon>
