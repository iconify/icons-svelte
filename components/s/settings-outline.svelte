<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bja55jb5m.css';
import '../../css/u/u6ndf9jqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="settings-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="bja55jb5m"/><path class="u6ndf9jqp"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:settings-outline" {...props}></Icon>
