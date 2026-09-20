<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7dawc.css';
import '../../css/t/t5pxry.css';
import '../../css/o/ovwh-q.css';
import '../../css/b/botfzx.css';
import '../../css/s/so-from-14.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGepJYqeIi"><path class="p7dawc t5pxry"/><path class="ovwh-q t5pxry"/></mask></defs><path mask="url(#SVGepJYqeIi)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:square-filled-to-confirm-square-filled-transition" {...props}></Icon>
