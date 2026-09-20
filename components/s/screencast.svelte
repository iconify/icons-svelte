<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/njoqz0rdx.css';
import '../../css/v/v0ahp5bvo.css';
import '../../css/b/bxqirsbqf.css';
import '../../css/h/h8p6umnvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="njoqz0rdx"/><path class="v0ahp5bvo"/><path class="bxqirsbqf"/><path class="h8p6umnvc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:screencast" {...props}></Icon>
