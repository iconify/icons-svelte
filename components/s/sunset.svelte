<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in9d5ac6n.css';
import '../../css/s/sy1nkmmcc.css';
import '../../css/p/phhmyrtui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="in9d5ac6n"><path class="sy1nkmmcc"/><path class="phhmyrtui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:sunset" {...props}></Icon>
