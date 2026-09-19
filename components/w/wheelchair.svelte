<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciq8kjb7u.css';
import '../../css/o/ob9cd8xhy.css';
import '../../css/a/av0rcu6kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ciq8kjb7u"/><path class="ob9cd8xhy"/><path class="av0rcu6kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wheelchair" {...props}></Icon>
