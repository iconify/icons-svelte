<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw6y4-jlg.css';
import '../../css/m/m9biyvb8g.css';
import '../../css/z/zrrxbeb2v.css';
import '../../css/t/tm0lw447f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw6y4-jlg"/><path class="m9biyvb8g"/><path class="zrrxbeb2v"/><path class="tm0lw447f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tulip" {...props}></Icon>
