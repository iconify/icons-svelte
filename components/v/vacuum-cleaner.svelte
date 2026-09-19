<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/f6vf_yxmf.css';
import '../../css/j/ja7_2f_3u.css';
import '../../css/e/ejt5gkbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6vf_yxmf"/><path class="ja7_2f_3u"/><path class="ejt5gkbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:vacuum-cleaner" {...props}></Icon>
