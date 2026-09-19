<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/x1aq_zb1l.css';
import '../../css/o/oblmn2yok.css';
import '../../css/y/yjo9i5b3u.css';
import '../../css/e/eg4xct43z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="x1aq_zb1l"/><path class="oblmn2yok"/><path class="yjo9i5b3u"/><path class="eg4xct43z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shopping-basket-done-02" {...props}></Icon>
