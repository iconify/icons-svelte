<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cj7qh-02u.css';
import '../../css/r/r8xumq8dh.css';
import '../../css/w/wvsuvupws.css';
import '../../css/j/ju0840bmy.css';
import '../../css/v/vjzau-ekp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="cj7qh-02u"/><path class="r8xumq8dh"/><path class="wvsuvupws"/><path class="ju0840bmy"/><path class="vjzau-ekp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:speech-to-text" {...props}></Icon>
