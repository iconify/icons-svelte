<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk9fdi05w.css';
import '../../css/e/exaqnd3xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk9fdi05w"/><path class="exaqnd3xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:shuffle" {...props}></Icon>
