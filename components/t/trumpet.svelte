<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v_ia9trwh.css';
import '../../css/i/i961peb9z.css';
import '../../css/e/et92v8bqb.css';
import '../../css/h/h5l4vccfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="v_ia9trwh"/><path class="i961peb9z"/><path class="et92v8bqb"/><path class="h5l4vccfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:trumpet" {...props}></Icon>
