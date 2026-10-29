<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a-99qbx0l.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/k/k55be6yhw.css';
import '../../css/c/ck-4ht99s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a-99qbx0l"/><path class="qr4ochb5c wm-s"/><path class="k55be6yhw"/><path class="ck-4ht99s wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:timer-off-duo" {...props}></Icon>
