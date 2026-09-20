<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnhb0dblg.css';
import '../../css/n/nd5uqlx5w.css';
import '../../css/o/os8fygsdg.css';
import '../../css/s/s16aoqb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cnhb0dblg"/><path class="nd5uqlx5w"/><path class="os8fygsdg"/><path class="s16aoqb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:transfer-zip-dark" {...props}></Icon>
