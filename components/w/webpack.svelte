<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe5dr5b9o.css';
import '../../css/h/hsqpd_2br.css';
import '../../css/a/anzwqbcxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe5dr5b9o"/><path class="hsqpd_2br"/><path class="anzwqbcxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:webpack" {...props}></Icon>
