<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6v-cu3kr.css';
import '../../css/o/o-mw0gu8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a6v-cu3kr"/><path class="o-mw0gu8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:settings-48" {...props}></Icon>
